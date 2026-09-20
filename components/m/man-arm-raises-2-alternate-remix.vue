<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mime5u9mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mime5u9mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:man-arm-raises-2-alternate-remix" /></template>
