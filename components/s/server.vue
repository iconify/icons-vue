<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/y/yen9g7bht.css';
import '../../css/m/mlcd-5bnp.css';
import '../../css/t/tekp_ab_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="yen9g7bht"/><path class="mlcd-5bnp"/><path class="tekp_ab_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:server" /></template>
