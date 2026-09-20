<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrgs-6b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrgs-6b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-sharp-fill" /></template>
