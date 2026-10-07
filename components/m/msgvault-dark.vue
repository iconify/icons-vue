<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp2n0tx7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mp2n0tx7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:msgvault-dark" /></template>
