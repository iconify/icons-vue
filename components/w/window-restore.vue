<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgp7bubto.css';
import '../../css/k/kbad1107b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgp7bubto"/><path class="kbad1107b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:window-restore" /></template>
