<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc46r_4jg.css';
import '../../css/r/r0a92247z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oc46r_4jg"/><path class="r0a92247z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:scrubber" /></template>
