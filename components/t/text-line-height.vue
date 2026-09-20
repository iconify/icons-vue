<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v4-9_wv8t.css';
import '../../css/t/t04y93jxd.css';
import '../../css/h/hk6vdne3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v4-9_wv8t"/><path class="t04y93jxd"/><path class="hk6vdne3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-line-height" /></template>
