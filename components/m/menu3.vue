<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j49n-pbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":16};
const content = `<path class="j49n-pbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:menu3" /></template>
