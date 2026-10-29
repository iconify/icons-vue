<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-5id0rms.css';
import '../../css/p/pxnosramj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k x-5id0rms"/><path class="pxnosramj wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shield-check" /></template>
