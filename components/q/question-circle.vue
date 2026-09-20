<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/y/y2h43n.css';
import '../../css/d/d-j1qi.css';
import '../../css/n/neinwl.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c y2h43n"/><path class="a0m25c d-j1qi"/><path class="a0m25c neinwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:question-circle" /></template>
