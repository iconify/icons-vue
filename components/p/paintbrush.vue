<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx17i_97r.css';
import '../../css/r/rnza0sb-x.css';
import '../../css/k/ke-2t-fwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx17i_97r wm-a"/><path class="rnza0sb-x wm-k"/><path class="ke-2t-fwz wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:paintbrush" /></template>
