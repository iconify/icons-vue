<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2qsx7eke.css';
import '../../css/e/e32k5njcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="e2qsx7eke"/><path class="e32k5njcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:old-navy" /></template>
