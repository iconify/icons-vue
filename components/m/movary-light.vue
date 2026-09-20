<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gra2o1ood.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gra2o1ood"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:movary-light" /></template>
