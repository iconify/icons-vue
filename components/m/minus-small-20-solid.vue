<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tti2g3bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tti2g3bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-small-20-solid" /></template>
