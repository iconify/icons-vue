<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3n9zob-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t3n9zob-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:view-split-20-solid" /></template>
