<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i73n831_u.css';
import '../../css/x/xl9hzbxpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i73n831_u"/><path class="xl9hzbxpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:report-slash" /></template>
