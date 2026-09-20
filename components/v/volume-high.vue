<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ms0wllv.css';
import '../../css/t/txxl_f0-v.css';
import '../../css/y/y7cusdbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="z9ms0wllv"/><path class="txxl_f0-v"/><path class="y7cusdbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume-high" /></template>
