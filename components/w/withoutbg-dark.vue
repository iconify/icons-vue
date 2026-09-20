<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czu-macwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czu-macwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:withoutbg-dark" /></template>
