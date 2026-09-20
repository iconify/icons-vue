<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx4asvbkn.css';
import '../../css/x/x9kjoyb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx4asvbkn"/><path class="x9kjoyb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:quora" /></template>
