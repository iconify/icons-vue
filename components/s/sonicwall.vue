<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf0a-7b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf0a-7b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sonicwall" /></template>
