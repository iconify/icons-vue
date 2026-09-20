<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd4b86b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd4b86b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro-sharp-duotone" /></template>
