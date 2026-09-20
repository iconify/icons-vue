<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmd9_ci0l.css';
import '../../css/v/vv1m_xbuq.css';
import '../../css/g/gv-p15bpi.css';
import '../../css/l/lwb5uprkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmd9_ci0l"/><path class="vv1m_xbuq"/><path clip-rule="evenodd" class="gv-p15bpi"/><path class="lwb5uprkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:paal" /></template>
