<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az58icbrr.css';
import '../../css/e/eezgffbcj.css';
import '../../css/z/z9r7tyb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="az58icbrr"/><circle class="eezgffbcj"/><path class="z9r7tyb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:medal-outline" /></template>
