<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhsrn1yyz.css';
import '../../css/j/jro2vlvum.css';
import '../../css/y/y0id5tbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhsrn1yyz"/><path class="jro2vlvum"/><path class="y0id5tbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:truck-16-solid" /></template>
