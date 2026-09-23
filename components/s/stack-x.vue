<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qllvo_fol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qllvo_fol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stack-x" /></template>
