<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4unsb2t.css';
import '../../css/f/fn009esdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yt4unsb2t"/><path class="fn009esdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash-20-solid" /></template>
