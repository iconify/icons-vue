<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc0y6abmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fc0y6abmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:transfer" /></template>
