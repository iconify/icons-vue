<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5pwaeu0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5pwaeu0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:paragraph-center-align" /></template>
