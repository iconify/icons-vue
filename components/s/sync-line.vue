<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrbcrlbrp.css';
import '../../css/k/kn1-sg2xn.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qrbcrlbrp"/><path class="clr-i-outline clr-i-outline-path-2 kn1-sg2xn"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:sync-line" /></template>
