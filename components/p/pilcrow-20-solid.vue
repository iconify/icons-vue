<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2yfoxp2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m2yfoxp2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow-20-solid" /></template>
