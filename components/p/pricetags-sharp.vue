<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udf6_wwmv.css';
import '../../css/l/lizw1zvth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udf6_wwmv"/><path class="lizw1zvth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pricetags-sharp" /></template>
