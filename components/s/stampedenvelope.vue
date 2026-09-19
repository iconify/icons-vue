<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suxitebkd.css';
import '../../css/y/yhpn0bbqq.css';
import '../../css/m/mxxkvj7yc.css';
import '../../css/l/lo5w_u_kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="suxitebkd"/><path class="yhpn0bbqq"/><path class="mxxkvj7yc"/><path class="lo5w_u_kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:stampedenvelope" /></template>
