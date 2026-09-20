<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mefg8obex.css';
import '../../css/i/ittidrwdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mefg8obex"/><path clip-rule="evenodd" class="ittidrwdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pedal-24" /></template>
