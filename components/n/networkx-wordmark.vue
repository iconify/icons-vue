<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_kyabxq.css';
import '../../css/q/qevuypzfx.css';
import '../../css/m/mkh8dfbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hu_kyabxq"/><path class="qevuypzfx"/><path class="mkh8dfbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:networkx-wordmark" /></template>
