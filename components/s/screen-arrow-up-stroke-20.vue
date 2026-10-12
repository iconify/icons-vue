<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzfb953yw.css';
import '../../css/n/n112oparr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzfb953yw"/><path class="n112oparr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:screen-arrow-up-stroke-20" /></template>
