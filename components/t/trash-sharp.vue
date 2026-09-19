<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfm5imxge.css';
import '../../css/i/i27ssqklb.css';
import '../../css/c/ce5djubef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfm5imxge"/><path class="i27ssqklb"/><path class="ce5djubef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trash-sharp" /></template>
