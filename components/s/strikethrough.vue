<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es1645-bw.css';
import '../../css/x/xzun-2bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es1645-bw wm-k"/><path class="wm-a xzun-2bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:strikethrough" /></template>
