<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ec5ibda.css';
import '../../css/z/z82ckhzmf.css';
import '../../css/j/jf_8h71yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l6ec5ibda"/><path class="z82ckhzmf"/><path class="jf_8h71yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:profilarr" /></template>
