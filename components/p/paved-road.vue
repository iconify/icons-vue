<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdrra_btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gdrra_btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:paved-road" /></template>
