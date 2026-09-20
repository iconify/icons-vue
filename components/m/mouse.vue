<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ura6pn2-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ura6pn2-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mouse" /></template>
