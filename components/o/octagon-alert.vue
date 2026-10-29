<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhs4dgblh.css';
import '../../css/x/xgp_bjbeh.css';
import '../../css/a/aqmrw1bwr.css';
import '../../css/k/k4kh0rbsg.css';
import '../../css/o/ogu4vlkot.css';
import '../../css/y/yzwlrvbmj.css';
import '../../css/v/vtl9vs2gh.css';
import '../../css/h/h4tfm49kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow zhs4dgblh"/><path class="wm-k xgp_bjbeh"/><path class="aqmrw1bwr wm-k"/><path class="k4kh0rbsg wm-k"/><path class="ogu4vlkot wm-k"/><path class="wm-k yzwlrvbmj"/><path class="vtl9vs2gh wm-shine"/><path class="h4tfm49kc wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:octagon-alert" /></template>
