<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohaoguboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohaoguboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-horizontal-sharp-fill" /></template>
