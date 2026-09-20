<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n90uq3bfu.css';
import '../../css/i/i1qy2-bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n90uq3bfu"/><path class="i1qy2-bfm ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-create-single-metric-job" /></template>
