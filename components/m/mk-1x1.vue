<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yapliwlbi.css';
import '../../css/i/iwjfocmqa.css';
import '../../css/m/mku189b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yapliwlbi"/><path class="iwjfocmqa"/><circle class="mku189b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mk-1x1" /></template>
