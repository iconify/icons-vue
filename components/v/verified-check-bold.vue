<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg3mb-7km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg3mb-7km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:verified-check-bold" /></template>
