<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b0l52zb1j.css';
import '../../css/u/ui_lws96b.css';
import '../../css/y/yl22r9bbu.css';
import '../../css/c/cdc_phbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b0l52zb1j"/><path class="ui_lws96b"/><path class="wm-a yl22r9bbu"/><path class="cdc_phbqy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wallet-cards" /></template>
