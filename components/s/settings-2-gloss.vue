<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lryf-jbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lryf-jbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:settings-2-gloss" /></template>
