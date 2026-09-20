<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq6-h0bqj.css';
import '../../css/q/qx_8ccc_v.css';
import '../../css/h/h8q8hfbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq6-h0bqj"/><path class="qx_8ccc_v"/><path class="h8q8hfbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:suku" /></template>
