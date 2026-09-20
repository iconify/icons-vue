<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iav0iacja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iav0iacja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:notification-application-1-remix" /></template>
