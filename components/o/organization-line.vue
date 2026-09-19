<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw8yjoqzh.css';
import '../../css/q/qjfrv1_4u.css';
import '../../css/h/hch8yvbvc.css';
import '../../css/l/lg_9hbc2k.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 dw8yjoqzh"/><path class="clr-i-outline clr-i-outline-path-2 qjfrv1_4u"/><path class="clr-i-outline clr-i-outline-path-3 hch8yvbvc"/><path class="clr-i-outline clr-i-outline-path-4 lg_9hbc2k"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:organization-line" /></template>
