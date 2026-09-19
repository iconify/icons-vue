<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo8ap71oo.css';
import '../../css/o/ooj3jip1b.css';
import '../../css/f/fhqdiozkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo8ap71oo"/><circle class="ooj3jip1b"/><circle class="fhqdiozkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:premium-network-tier" /></template>
