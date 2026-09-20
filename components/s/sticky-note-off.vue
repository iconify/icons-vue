<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtt3ujtqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtt3ujtqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-off" /></template>
