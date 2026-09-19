<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grc_u9byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grc_u9byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:snowflake" /></template>
