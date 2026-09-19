<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5v0brb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5v0brb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:package-filled" /></template>
