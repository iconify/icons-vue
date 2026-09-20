<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld_nlfa0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_nlfa0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scales-3-line" /></template>
