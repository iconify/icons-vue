<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_d-kbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sw_d-kbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:replyd" /></template>
