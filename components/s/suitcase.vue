<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov51f8b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ov51f8b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:suitcase" /></template>
