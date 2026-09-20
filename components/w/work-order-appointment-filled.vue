<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7qlfbcri.css';
import '../../css/q/qcjn5ubrr.css';
import '../../css/g/g_l_olm7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e7qlfbcri"/><path class="qcjn5ubrr"/><path clip-rule="evenodd" class="g_l_olm7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-appointment-filled" /></template>
