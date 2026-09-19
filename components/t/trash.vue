<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnv7bpbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bnv7bpbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:trash" /></template>
