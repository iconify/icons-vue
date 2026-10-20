<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzclhm7wd.css';
import '../../css/l/lv7wocbph.css';
import '../../css/c/cc4mncs3v.css';
import '../../css/n/n330h3bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35.402,"height":11.519};
const content = `<path class="hzclhm7wd"/><path class="lv7wocbph"/><path class="cc4mncs3v"/><path class="n330h3bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oporto" /></template>
