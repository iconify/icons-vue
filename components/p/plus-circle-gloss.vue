<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgvbnbcfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgvbnbcfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plus-circle-gloss" /></template>
