<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdqyy1btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdqyy1btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-cancel" /></template>
