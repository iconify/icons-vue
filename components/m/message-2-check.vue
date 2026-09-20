<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivl5r6cnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivl5r6cnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-check" /></template>
