<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaiv0cbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaiv0cbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-note-add-outline" /></template>
