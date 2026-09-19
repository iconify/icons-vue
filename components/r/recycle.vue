<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow5n59_vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ow5n59_vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:recycle" /></template>
