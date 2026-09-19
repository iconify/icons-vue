<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6ndv5-vm.css';
import '../../css/f/fiwf45bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<rect class="p6ndv5-vm"/><path class="fiwf45bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-fill-12" /></template>
