<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/punal9bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":661};
const content = `<path class="punal9bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:wifi" /></template>
