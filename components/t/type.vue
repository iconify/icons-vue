<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3_i02i0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_i02i0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:type" /></template>
