<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wlk7cymyb.css';
import '../../css/m/mio52ig2b.css';
import '../../css/y/yh3pvrblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wlk7cymyb"/><circle class="mio52ig2b"/><path class="yh3pvrblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:users-round" /></template>
