<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr1vn-rwh.css';
import '../../css/v/v904cs9gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tr1vn-rwh"/><path class="v904cs9gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raneto-light" /></template>
