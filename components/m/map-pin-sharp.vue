<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbjkxcc6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbjkxcc6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-sharp" /></template>
