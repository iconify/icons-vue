<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twud3tbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twud3tbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-x" /></template>
