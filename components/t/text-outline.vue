<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuds1jrnr.css';
import '../../css/a/a_u_vcn1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kuds1jrnr"/><path class="a_u_vcn1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:text-outline" /></template>
