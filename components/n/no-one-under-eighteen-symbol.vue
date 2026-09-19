<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7d6iacxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s7d6iacxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:no-one-under-eighteen-symbol" /></template>
