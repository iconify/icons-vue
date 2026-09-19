<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebpowfb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebpowfb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-edit-filled" /></template>
