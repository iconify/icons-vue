<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snfd_jbqj.css';
import '../../css/d/d7v_hcc-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snfd_jbqj"/><path class="d7v_hcc-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pricetag-outline" /></template>
