<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0t26ccmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v0t26ccmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:play-store-fill" /></template>
