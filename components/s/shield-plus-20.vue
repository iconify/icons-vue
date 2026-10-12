<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-pj4obxj.css';
import '../../css/c/c6gzs9dks.css';
import '../../css/q/qy_x_gaft.css';
import '../../css/e/evng24apc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-pj4obxj"/><path class="c6gzs9dks"/><path class="qy_x_gaft"/><path class="evng24apc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-plus-20" /></template>
