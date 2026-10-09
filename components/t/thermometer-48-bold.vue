<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6yqgv8r.css';
import '../../css/i/iebf4fbnh.css';
import '../../css/c/cp_vdbbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly6yqgv8r"/><path class="iebf4fbnh"/><path class="cp_vdbbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-48-bold" /></template>
