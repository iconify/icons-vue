<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip-6gzbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip-6gzbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-check-filled" /></template>
