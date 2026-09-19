<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfm5imxge.css';
import '../../css/u/u5ykzlbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfm5imxge"/><path class="u5ykzlbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trash" /></template>
