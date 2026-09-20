<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5h4oig5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g5h4oig5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:notification-alarm-snooze-remix" /></template>
