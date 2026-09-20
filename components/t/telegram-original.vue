<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drjbh1b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="drjbh1b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:telegram-original" /></template>
