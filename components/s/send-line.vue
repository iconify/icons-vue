<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n12-wsb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n12-wsb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:send-line" /></template>
