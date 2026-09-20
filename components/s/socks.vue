<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aks-r-baq.css';
import '../../css/q/qm97rya6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aks-r-baq"/><path class="qm97rya6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:socks" /></template>
