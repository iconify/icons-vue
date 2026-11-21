<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0szqpn1j.css';
import '../../css/a/a_u_vcn1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0szqpn1j"/><path class="a_u_vcn1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:text-outline" /></template>
