<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4iz7n-id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4iz7n-id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:receipt-solid" /></template>
