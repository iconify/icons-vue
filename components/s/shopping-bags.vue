<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uexuiinxx.css';
import '../../css/v/vi7of3bpv.css';
import '../../css/g/guzqa6bjs.css';
import '../../css/g/g7lf7dbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uexuiinxx"/><path class="vi7of3bpv"/><path class="guzqa6bjs"/><path class="g7lf7dbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shopping-bags" /></template>
