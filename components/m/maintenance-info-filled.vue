<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtd4wbceg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtd4wbceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-info-filled" /></template>
