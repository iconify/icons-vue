<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxwjsibxu.css';
import '../../css/t/trpnkyp1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fxwjsibxu"/><path class="trpnkyp1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zohomail" /></template>
