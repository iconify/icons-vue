<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oedqgxdbn.css';
import '../../css/l/lhboxdbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oedqgxdbn"/><path class="lhboxdbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat-dark" /></template>
