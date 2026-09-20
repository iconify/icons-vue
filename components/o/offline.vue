<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r50oo_b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r50oo_b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:offline" /></template>
