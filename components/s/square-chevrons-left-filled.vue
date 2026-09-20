<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_3ee6a8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_3ee6a8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-chevrons-left-filled" /></template>
