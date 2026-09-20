<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo63pfbjq.css';
import '../../css/w/weqsqjbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oo63pfbjq"/><path clip-rule="evenodd" class="weqsqjbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:youtube-16" /></template>
