<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg4bhfbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg4bhfbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zap-off" /></template>
