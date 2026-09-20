<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gti885y0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gti885y0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:taichi-lang" /></template>
