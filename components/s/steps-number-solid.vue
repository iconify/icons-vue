<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr8rlhbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr8rlhbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:steps-number-solid" /></template>
