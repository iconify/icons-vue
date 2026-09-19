<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/go2hddcxj.css';
import '../../css/i/i5wjkl-nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":32};
const content = `<g class="cuyn6tgcc"><path class="go2hddcxj"/><path class="i5wjkl-nm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:strategy" /></template>
