<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t222qp1dw.css';
import '../../css/t/tpohchbcz.css';
import '../../css/m/mq6pl43bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t222qp1dw wm-k"/><path class="tpohchbcz wm-a"/><path class="mq6pl43bl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:message-circle-more" /></template>
