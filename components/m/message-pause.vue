<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtf9udbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtf9udbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-pause" /></template>
