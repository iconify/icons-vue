<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljsebdbqo.css';
import '../../css/k/kb7eai5rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ljsebdbqo"/><path class="kb7eai5rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:target-revenue" /></template>
