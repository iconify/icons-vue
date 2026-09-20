<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nn08obcli.css';
import '../../css/w/w1jdr8bjq.css';
import '../../css/e/evevsc90e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nn08obcli"/><path class="w1jdr8bjq"/><path class="evevsc90e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:notification-error" /></template>
