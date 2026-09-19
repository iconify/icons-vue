<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/o/olsnk6fpy.css';
import '../../css/z/z9wgtxbsj.css';
import '../../css/f/fpixpmx3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="olsnk6fpy"/><path class="z9wgtxbsj"/><path class="fpixpmx3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:reload" /></template>
