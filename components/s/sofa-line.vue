<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osv-pcb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osv-pcb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sofa-line" /></template>
