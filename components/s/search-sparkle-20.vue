<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6amyqet.css';
import '../../css/y/yoyl5gbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq6amyqet"/><path class="yoyl5gbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-sparkle-20" /></template>
