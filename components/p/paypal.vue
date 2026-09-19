<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muo3kxbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muo3kxbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:paypal" /></template>
