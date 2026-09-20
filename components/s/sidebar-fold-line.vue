<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb023bcmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb023bcmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sidebar-fold-line" /></template>
