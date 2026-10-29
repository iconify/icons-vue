<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_6p9c4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it_6p9c4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rewind-solid" /></template>
