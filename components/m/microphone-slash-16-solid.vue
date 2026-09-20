<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq42nebwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mq42nebwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash-16-solid" /></template>
