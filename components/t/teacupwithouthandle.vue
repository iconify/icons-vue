<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge30c7t1y.css';
import '../../css/q/qlod68b4m.css';
import '../../css/o/owaw-8bmd.css';
import '../../css/h/hl25b9hpu.css';
import '../../css/b/b93a7obub.css';
import '../../css/c/csq3f9b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ge30c7t1y"/><path class="qlod68b4m"/><path class="owaw-8bmd"/><path class="hl25b9hpu"/><path class="b93a7obub"/><path class="csq3f9b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:teacupwithouthandle" /></template>
