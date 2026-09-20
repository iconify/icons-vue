<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdortxboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdortxboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:voice-cricle-filled" /></template>
