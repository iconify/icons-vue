<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2kn6fadi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2kn6fadi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-x" /></template>
