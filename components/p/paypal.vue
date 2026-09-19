<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo1k5b-e.css';
import '../../css/n/nlqvrrg1h.css';
import '../../css/n/nniesdbig.css';
import '../../css/j/jaw_f2b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="nlqvrrg1h"/><path class="nniesdbig"/><path class="jaw_f2b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:paypal" /></template>
