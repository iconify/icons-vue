<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmvw-64_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmvw-64_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-filled" /></template>
