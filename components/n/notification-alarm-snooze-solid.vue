<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud109lbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ud109lbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:notification-alarm-snooze-solid" /></template>
