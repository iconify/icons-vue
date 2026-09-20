<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2b9f33ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2b9f33ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message" /></template>
