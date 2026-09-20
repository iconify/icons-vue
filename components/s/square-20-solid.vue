<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4lzkobkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n4lzkobkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:square-20-solid" /></template>
