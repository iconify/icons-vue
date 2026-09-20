<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la86yvriw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la86yvriw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:maximize-2-two-tone" /></template>
