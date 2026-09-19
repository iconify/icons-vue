<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9darvblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9darvblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-star-filled" /></template>
