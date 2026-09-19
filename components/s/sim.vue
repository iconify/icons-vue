<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxd28wbfb.css';
import '../../css/j/jpb-onl0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxd28wbfb"/><path class="jpb-onl0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sim" /></template>
