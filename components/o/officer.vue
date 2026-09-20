<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw3gm_bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iw3gm_bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:officer" /></template>
