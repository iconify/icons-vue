<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yerfd1kgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yerfd1kgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-call-gloss" /></template>
