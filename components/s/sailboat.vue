<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/f1msnb5-c.css';
import '../../css/p/pshki8f7n.css';
import '../../css/d/dtmyh0hhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="f1msnb5-c"/><path class="pshki8f7n"/><path class="dtmyh0hhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:sailboat" /></template>
