<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtmsfsbcp.css';
import '../../css/e/e041-1bai.css';
import '../../css/e/eika0rrpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="jtmsfsbcp"/><circle class="e041-1bai"/><circle class="eika0rrpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:more-alt" /></template>
