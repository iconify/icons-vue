<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6hs9ongt.css';
import '../../css/v/vj13mgbku.css';
import '../../css/n/nms6vjb0u.css';
import '../../css/k/ky84c4vcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6hs9ongt wm-k"/><path class="vj13mgbku wm-a"/><path class="nms6vjb0u wm-a"/><path class="ky84c4vcl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:palette" /></template>
