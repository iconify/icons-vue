<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ica_bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g8ica_bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-x" /></template>
