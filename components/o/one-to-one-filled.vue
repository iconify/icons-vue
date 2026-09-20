<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq8al8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oq8al8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:one-to-one-filled" /></template>
