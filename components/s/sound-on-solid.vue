<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz335zj5g.css';
import '../../css/u/ux2qx_n6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz335zj5g"/><path class="ux2qx_n6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sound-on-solid" /></template>
