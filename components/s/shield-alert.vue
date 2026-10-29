<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6cq0z4kl.css';
import '../../css/m/m47_gshyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6cq0z4kl wm-k"/><path class="m47_gshyo wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shield-alert" /></template>
