<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en-8bjbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en-8bjbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:message-circle-fill" /></template>
