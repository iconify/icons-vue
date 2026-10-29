<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wup9xabdg.css';
import '../../css/w/wlwgd_xcs.css';
import '../../css/d/d84faeanp.css';
import '../../css/h/hyiuzhbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a wup9xabdg"/><path class="wlwgd_xcs wm-a"/><path class="d84faeanp wm-k"/><path class="hyiuzhbmd wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:soup" /></template>
