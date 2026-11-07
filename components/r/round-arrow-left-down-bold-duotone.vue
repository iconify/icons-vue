<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtmuzrg2o.css';
import '../../css/k/kcxg56bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path class="kcxg56bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-down-bold-duotone" /></template>
