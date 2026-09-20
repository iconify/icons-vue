<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i21b6im-e.css';
import '../../css/c/ci5n4gb-o.css';
import '../../css/p/pl7c8r-zm.css';
import '../../css/z/zf57u6bez.css';
import '../../css/q/q_b7ivbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="i21b6im-e"/><circle class="ci5n4gb-o"/><circle class="pl7c8r-zm"/><path class="zf57u6bez"/><path class="q_b7ivbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transfer-zip" /></template>
