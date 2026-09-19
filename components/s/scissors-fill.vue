<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqe620tbb.css';
import '../../css/n/nxaii_ued.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqe620tbb"/><path class="nxaii_ued"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:scissors-fill" /></template>
