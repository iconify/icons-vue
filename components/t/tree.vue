<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/da0su4uhx.css';
import '../../css/t/tfi0d09kv.css';
import '../../css/s/s5bjb7baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="da0su4uhx"/><path class="tfi0d09kv"/><path class="s5bjb7baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:tree" /></template>
