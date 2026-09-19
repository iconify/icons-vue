<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivom5o5ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivom5o5ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-image-filled" /></template>
