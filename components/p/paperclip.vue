<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_wme-api.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s_wme-api"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:paperclip" /></template>
