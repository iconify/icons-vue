<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqu5lsb_r.css';
import '../../css/e/e09mkx9uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqu5lsb_r"/><path clip-rule="evenodd" class="e09mkx9uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:reddit" /></template>
