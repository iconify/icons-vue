<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfuueobig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfuueobig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mailbox-line" /></template>
