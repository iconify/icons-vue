<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egv8nrbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egv8nrbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:n8n" /></template>
