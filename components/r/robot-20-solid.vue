<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtnufg-lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vtnufg-lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:robot-20-solid" /></template>
