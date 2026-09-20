<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogoznx9lr.css';
import '../../css/m/mabwzbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ogoznx9lr"/><path class="mabwzbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:plus-circle" /></template>
