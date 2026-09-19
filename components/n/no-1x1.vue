<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6e3-5bus.css';
import '../../css/d/dxcl0tb7m.css';
import '../../css/i/iufaf7g1w.css';
import '../../css/x/xj85fqn8n.css';
import '../../css/k/kbkdv3xcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6e3-5bus"/><path class="dxcl0tb7m"/><path class="iufaf7g1w"/><path class="xj85fqn8n"/><path class="kbkdv3xcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:no-1x1" /></template>
