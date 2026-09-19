<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxitz_43v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxitz_43v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:wpbeginner" /></template>
