<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjcugmbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="cjcugmbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:paypal" /></template>
