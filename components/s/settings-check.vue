<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffyaq1wcl.css';
import '../../css/i/i-d09ab5o.css';
import '../../css/p/p7o_o6bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ffyaq1wcl"/><path class="i-d09ab5o"/><path class="p7o_o6bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings-check" /></template>
