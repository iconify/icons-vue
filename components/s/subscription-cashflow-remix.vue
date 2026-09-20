<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua-tsqzzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ua-tsqzzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subscription-cashflow-remix" /></template>
