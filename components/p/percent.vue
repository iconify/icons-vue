<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hrjfpsb2u.css';
import '../../css/o/oqdxdpjwb.css';
import '../../css/p/pdzzspcnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="hrjfpsb2u"/><path class="oqdxdpjwb"/><circle class="pdzzspcnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:percent" /></template>
