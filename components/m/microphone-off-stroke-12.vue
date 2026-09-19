<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-rojbqe.css';
import '../../css/n/n6od47b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gu-rojbqe"/><path class="n6od47b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-off-stroke-12" /></template>
