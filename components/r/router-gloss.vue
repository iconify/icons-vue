<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwt69b86a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwt69b86a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:router-gloss" /></template>
