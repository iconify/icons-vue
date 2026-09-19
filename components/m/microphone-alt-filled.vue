<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfmxxebmr.css';
import '../../css/j/j6k0-dpwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfmxxebmr"/><path class="j6k0-dpwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-alt-filled" /></template>
