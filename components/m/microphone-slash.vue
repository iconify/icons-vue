<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iln50bcxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iln50bcxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:microphone-slash" /></template>
