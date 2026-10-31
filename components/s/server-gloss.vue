<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss72x250m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss72x250m wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-gloss" /></template>
