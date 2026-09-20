<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x704wfbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x704wfbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-filled" /></template>
