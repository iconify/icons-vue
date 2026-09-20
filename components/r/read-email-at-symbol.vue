<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqao3fb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqao3fb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:read-email-at-symbol" /></template>
