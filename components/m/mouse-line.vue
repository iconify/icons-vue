<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd3r8ab0o.css';
import '../../css/h/hfbateitc.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 hd3r8ab0o"/><path class="clr-i-outline clr-i-outline-path-2 hfbateitc"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:mouse-line" /></template>
