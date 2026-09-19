<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5wf9mbzr.css';
import '../../css/o/o0r6dnbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5wf9mbzr"/><path class="o0r6dnbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:pe-1x1" /></template>
