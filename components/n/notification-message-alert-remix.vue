<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4i95ksyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r4i95ksyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-message-alert-remix" /></template>
