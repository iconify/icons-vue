<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qrfxe7bdo.css';
import '../../css/h/h8wb40b9m.css';
import '../../css/x/xac-pkbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qrfxe7bdo"/><path class="h8wb40b9m wm-a"/><path class="xac-pkbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sandwich-duo" /></template>
