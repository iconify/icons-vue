<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz5j0eb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz5j0eb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nexon" /></template>
