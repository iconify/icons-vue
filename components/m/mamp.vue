<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crb39fbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crb39fbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mamp" /></template>
