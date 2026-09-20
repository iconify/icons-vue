<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn43otbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn43otbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-up" /></template>
