<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_b_b2b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_b_b2b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paperclip-x" /></template>
