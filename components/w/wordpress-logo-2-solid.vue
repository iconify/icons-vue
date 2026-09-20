<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_e_ok3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rv_e_ok3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wordpress-logo-2-solid" /></template>
