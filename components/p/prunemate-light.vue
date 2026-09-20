<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5hjy_sli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5hjy_sli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prunemate-light" /></template>
