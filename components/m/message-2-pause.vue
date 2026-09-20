<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twqi1ol-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twqi1ol-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-pause" /></template>
