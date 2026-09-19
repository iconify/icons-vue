<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swj8w_bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="swj8w_bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:merge" /></template>
