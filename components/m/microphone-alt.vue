<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzxa7rbby.css';
import '../../css/j/jfmxxebmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzxa7rbby"/><path class="jfmxxebmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-alt" /></template>
