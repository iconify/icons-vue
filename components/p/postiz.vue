<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6mte0bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6mte0bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:postiz" /></template>
