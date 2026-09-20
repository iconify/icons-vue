<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iurr2qbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iurr2qbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:viddler-logo-block" /></template>
