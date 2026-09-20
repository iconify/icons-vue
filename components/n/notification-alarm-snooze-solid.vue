<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8f87eb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8f87eb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:notification-alarm-snooze-solid" /></template>
