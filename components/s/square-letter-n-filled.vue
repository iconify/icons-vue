<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry-jzed8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry-jzed8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-n-filled" /></template>
