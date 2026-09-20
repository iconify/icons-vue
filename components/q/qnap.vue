<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhie0db7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhie0db7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:qnap" /></template>
