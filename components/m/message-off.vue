<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7w8xj34l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7w8xj34l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-off" /></template>
