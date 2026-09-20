<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikjp-dbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikjp-dbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-plus" /></template>
