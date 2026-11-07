<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hao-y3_km.css';
import '../../css/c/csp4cxb4v.css';
import '../../css/p/ptrg_gs-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-y3_km"/><path class="csp4cxb4v"/><path class="ptrg_gs-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-left-bold-duotone" /></template>
