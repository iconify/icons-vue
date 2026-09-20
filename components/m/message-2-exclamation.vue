<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpfa72wmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpfa72wmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-exclamation" /></template>
