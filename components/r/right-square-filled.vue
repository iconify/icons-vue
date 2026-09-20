<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiuj1-afm.css';
import '../../css/w/wd15b2bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yiuj1-afm"/><path clip-rule="evenodd" class="wd15b2bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:right-square-filled" /></template>
