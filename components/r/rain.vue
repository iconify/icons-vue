<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os67eymuh.css';
import '../../css/s/sg7qdup6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="os67eymuh"/><path class="sg7qdup6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:rain" /></template>
