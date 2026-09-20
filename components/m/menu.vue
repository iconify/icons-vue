<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/b/bv_l28bpi.css';
import '../../css/p/pailr-q6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><rect class="bv_l28bpi"/><rect class="pailr-q6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:menu" /></template>
