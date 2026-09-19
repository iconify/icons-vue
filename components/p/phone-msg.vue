<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oprfdnb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="oprfdnb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-msg" /></template>
