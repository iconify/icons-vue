<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b99mwcchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b99mwcchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-merge-cells" /></template>
