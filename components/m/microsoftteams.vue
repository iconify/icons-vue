<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt506yb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt506yb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftteams" /></template>
