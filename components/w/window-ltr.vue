<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3epgsb1m.css';
import '../../css/h/hu6j50bjd.css';
import '../../css/f/f_ebgjbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x3epgsb1m"/><path class="hu6j50bjd"/><circle class="f_ebgjbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:window-ltr" /></template>
