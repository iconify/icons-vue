<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tadldac1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tadldac1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sharp" /></template>
