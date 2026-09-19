<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svv79rwwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svv79rwwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-reply-filled" /></template>
