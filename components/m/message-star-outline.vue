<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm46kiyup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm46kiyup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-star-outline" /></template>
