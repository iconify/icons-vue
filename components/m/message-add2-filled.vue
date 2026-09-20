<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-moc8btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-moc8btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-add2-filled" /></template>
