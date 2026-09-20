<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtav2zbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtav2zbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:woocommerce-logo-block" /></template>
