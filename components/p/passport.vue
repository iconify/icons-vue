<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkxqx5p1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkxqx5p1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:passport" /></template>
