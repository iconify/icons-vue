<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/c/cxjz-n.css';
import '../../css/k/k3detq.css';
import '../../css/l/lo698u.css';
import '../../css/d/dy_5ci.css';
import '../../css/q/qr4g-m.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c cxjz-n"/><path class="a0m25c k3detq"/><path class="a0m25c lo698u"/><path class="a0m25c dy_5ci"/><path class="a0m25c qr4g-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:telegram" /></template>
