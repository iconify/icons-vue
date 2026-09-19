<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdgd-5r7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdgd-5r7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:truck" /></template>
