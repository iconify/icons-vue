<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-zu11bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t-zu11bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rheumatology" /></template>
