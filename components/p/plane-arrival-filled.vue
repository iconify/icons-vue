<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d28cjibda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d28cjibda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-arrival-filled" /></template>
