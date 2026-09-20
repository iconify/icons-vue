<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8dn3xito.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8dn3xito"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-reply-sharp" /></template>
