<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr4r3o7xw.css';
import '../../css/u/ule9-cczc.css';
import '../../css/d/dapyzkble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="lr4r3o7xw"/><rect class="ule9-cczc"/><rect class="dapyzkble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:menu-outline" /></template>
