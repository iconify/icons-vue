<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h96oc06ai.css';
import '../../css/s/srkn7eb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h96oc06ai"/><path class="srkn7eb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:stethoscope-alt" /></template>
