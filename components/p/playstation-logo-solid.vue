<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2ex7k_ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2ex7k_ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:playstation-logo-solid" /></template>
