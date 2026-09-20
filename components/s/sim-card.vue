<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbokte67o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbokte67o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:sim-card" /></template>
