<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbtv_rbic.css';
import '../../css/e/ea8if3c8i.css';
import '../../css/m/mgzrqm6_d.css';
import '../../css/k/kat0eym1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbtv_rbic"/><path class="ea8if3c8i"/><path class="mgzrqm6_d"/><path class="kat0eym1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:ruler-combined" /></template>
