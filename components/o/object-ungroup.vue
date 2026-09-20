<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf0y5u_qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf0y5u_qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:object-ungroup" /></template>
