<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcpgq_b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcpgq_b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:o-reilly" /></template>
