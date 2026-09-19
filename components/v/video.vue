<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbswx-bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pbswx-bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:video" /></template>
