<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilq7c980s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq7c980s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-user" /></template>
