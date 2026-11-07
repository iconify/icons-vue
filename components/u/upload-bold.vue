<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2--zlbhj.css';
import '../../css/j/jqzwqyd4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2--zlbhj"/><path class="jqzwqyd4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-bold" /></template>
