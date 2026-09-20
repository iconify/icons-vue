<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbl884bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fbl884bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:twitter-original" /></template>
