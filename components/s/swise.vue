<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6i609scc.css';
import '../../css/c/cnc48xb-n.css';
import '../../css/r/rtbltcbsy.css';
import '../../css/a/au6cvt0tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6i609scc"/><path class="cnc48xb-n"/><path class="rtbltcbsy"/><path class="au6cvt0tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:swise" /></template>
