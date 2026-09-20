<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwdt2v70o.css';
import '../../css/k/kqe51pb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwdt2v70o"/><path class="kqe51pb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usps" /></template>
