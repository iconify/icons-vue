<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9vqu.css';
import '../../css/q/qa-o7h.css';
import '../../css/c/cjd4hj.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9vqu qa-o7h"/><path class="cjd4hj qa-o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:valign-baseline" /></template>
