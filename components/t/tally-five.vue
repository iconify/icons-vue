<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udy-fib_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udy-fib_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:tally-five" /></template>
