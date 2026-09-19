<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of1ohj7_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of1ohj7_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vpn-connection" /></template>
