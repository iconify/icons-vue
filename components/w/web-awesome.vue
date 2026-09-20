<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkap942sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkap942sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:web-awesome" /></template>
