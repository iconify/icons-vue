<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqkvepb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqkvepb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:petroleum-solvent-steam" /></template>
