<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-oqepbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-oqepbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:melon-filled" /></template>
