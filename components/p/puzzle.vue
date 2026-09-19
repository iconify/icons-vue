<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4hcmvbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4hcmvbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:puzzle" /></template>
