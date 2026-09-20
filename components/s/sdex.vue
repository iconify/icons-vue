<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp06xm10d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp06xm10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sdex" /></template>
