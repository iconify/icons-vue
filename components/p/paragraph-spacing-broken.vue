<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e55mrdbou.css';
import '../../css/b/bq0ypf47a.css';
import '../../css/i/iim04tfhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e55mrdbou"/><path class="bq0ypf47a"/><path class="iim04tfhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paragraph-spacing-broken" /></template>
