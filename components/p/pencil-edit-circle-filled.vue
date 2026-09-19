<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdtpq1bge.css';
import '../../css/l/l2x5o3qgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtpq1bge"/><path class="l2x5o3qgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-edit-circle-filled" /></template>
