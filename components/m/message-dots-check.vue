<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5a5l6b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5a5l6b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-dots-check" /></template>
