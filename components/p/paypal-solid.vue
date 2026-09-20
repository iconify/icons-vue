<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfpigabpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mfpigabpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paypal-solid" /></template>
