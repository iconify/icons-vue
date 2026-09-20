<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/not_us-ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="not_us-ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:uno" /></template>
