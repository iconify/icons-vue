<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1lgfrm_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d1lgfrm_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-half-20-solid" /></template>
