<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psk9ti-eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psk9ti-eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wall-filled" /></template>
