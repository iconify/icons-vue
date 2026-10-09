<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjifzhf9x.css';
import '../../css/n/n3w40giun.css';
import '../../css/u/uem-t2b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xjifzhf9x"/><path class="n3w40giun"/><path class="uem-t2b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paint-bucket-48-bold" /></template>
