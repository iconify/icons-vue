<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tehefibtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tehefibtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:no-meeting-room" /></template>
