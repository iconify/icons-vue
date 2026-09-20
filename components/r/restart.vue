<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwk2mab9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwk2mab9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:restart" /></template>
