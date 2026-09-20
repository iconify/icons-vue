<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6sztackv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6sztackv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:web-check-dark" /></template>
