<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlm8c2bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qlm8c2bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:radiation" /></template>
