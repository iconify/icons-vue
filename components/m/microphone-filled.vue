<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byqra4-jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byqra4-jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:microphone-filled" /></template>
