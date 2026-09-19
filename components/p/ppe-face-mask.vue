<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvarblb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fvarblb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-face-mask" /></template>
