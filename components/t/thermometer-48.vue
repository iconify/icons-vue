<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyzjbf5oz.css';
import '../../css/b/bs8u9-bib.css';
import '../../css/d/dz2xsntoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyzjbf5oz"/><path class="bs8u9-bib"/><path class="dz2xsntoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-48" /></template>
