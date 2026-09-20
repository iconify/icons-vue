<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo_gcl4jc.css';
import '../../css/d/dp0jygg6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oo_gcl4jc"/><path class="dp0jygg6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rackula" /></template>
