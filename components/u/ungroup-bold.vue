<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdm667-fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bdm667-fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ungroup-bold" /></template>
