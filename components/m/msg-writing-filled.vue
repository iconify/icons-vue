<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aamnv1bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aamnv1bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:msg-writing-filled" /></template>
