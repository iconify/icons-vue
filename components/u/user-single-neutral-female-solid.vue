<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5_cdvbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5_cdvbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-single-neutral-female-solid" /></template>
