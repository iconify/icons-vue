<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if1bcwb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if1bcwb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:notification-alarm-snooze-remix" /></template>
