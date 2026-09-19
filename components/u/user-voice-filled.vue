<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmp9nzblx.css';
import '../../css/f/fnb-t_u4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmp9nzblx"/><path class="fnb-t_u4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-voice-filled" /></template>
