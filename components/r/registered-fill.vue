<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcpn8ebbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcpn8ebbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:registered-fill" /></template>
