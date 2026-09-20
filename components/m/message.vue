<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etl64wbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etl64wbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:message" /></template>
