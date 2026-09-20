<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noegfwg_l.css';
import '../../css/r/r-a7fhb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="noegfwg_l"/><path class="r-a7fhb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:mental-health" /></template>
