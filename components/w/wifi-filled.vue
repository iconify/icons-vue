<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks-rnpbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ks-rnpbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:wifi-filled" /></template>
