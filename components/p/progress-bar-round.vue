<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixz9bpndl.css';
import '../../css/b/bqehyh14p.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixz9bpndl"/><path class="bqehyh14p"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:progress-bar-round" /></template>
