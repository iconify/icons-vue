<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd475mn6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd475mn6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-down" /></template>
