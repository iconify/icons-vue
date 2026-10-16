<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab2lv3v6m.css';
import '../../css/t/t8akbzbjd.css';
import '../../css/l/loe-m_xnw.css';
import '../../css/y/yjuc4h0xr.css';
import '../../css/n/nq5_p_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ab2lv3v6m"/><path class="t8akbzbjd"/><path class="loe-m_xnw"/><path class="yjuc4h0xr"/><path class="nq5_p_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tracker-alert-20" /></template>
