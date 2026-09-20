<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ano20bb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ano20bb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pingdom" /></template>
