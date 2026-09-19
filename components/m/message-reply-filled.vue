<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkfqnwb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkfqnwb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-reply-filled" /></template>
