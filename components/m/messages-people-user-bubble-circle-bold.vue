<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsx3c6bcc.css';
import '../../css/e/elgr7ftla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsx3c6bcc"/><path class="elgr7ftla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-people-user-bubble-circle-bold" /></template>
