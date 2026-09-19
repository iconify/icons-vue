<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scmdz_bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="scmdz_bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:stubber" /></template>
