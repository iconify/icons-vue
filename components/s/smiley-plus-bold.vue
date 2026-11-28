<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnw1wt3zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jnw1wt3zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:smiley-plus-bold" /></template>
