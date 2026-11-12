<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1v2sdoj.css';
import '../../css/f/flltnf0xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="flltnf0xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-contacts" /></template>
