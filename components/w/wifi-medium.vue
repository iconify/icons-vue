<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk1sc4blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk1sc4blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-medium" /></template>
