<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g97jyebka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g97jyebka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-minus-filled" /></template>
