<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_qceb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lc_qceb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parrot" /></template>
