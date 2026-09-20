<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhrq4ibex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vhrq4ibex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ringing-bell-notification-solid" /></template>
