<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaqxp6zrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaqxp6zrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ticket-line" /></template>
