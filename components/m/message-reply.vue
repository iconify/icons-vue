<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3rkaac-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3rkaac-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-reply" /></template>
