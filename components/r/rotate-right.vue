<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezfumgw-x.css';
import '../../css/e/e16bk6emp.css';
import '../../css/p/p62-edcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ezfumgw-x"><path class="e16bk6emp"/><path class="p62-edcjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:rotate-right" /></template>
