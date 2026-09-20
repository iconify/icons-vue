<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guc56fbsq.css';
import '../../css/b/bqc81ux0g.css';
import '../../css/a/amspxabxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guc56fbsq"/><path class="bqc81ux0g"/><path class="amspxabxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:society" /></template>
