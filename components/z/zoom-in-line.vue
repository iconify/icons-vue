<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_zoepac.css';
import '../../css/z/zov54cbdm.css';
import '../../css/z/zz20r9bzu.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 er_zoepac"/><path class="clr-i-outline clr-i-outline-path-2 zov54cbdm"/><path class="clr-i-outline clr-i-outline-path-3 zz20r9bzu"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:zoom-in-line" /></template>
