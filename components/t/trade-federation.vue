<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyvonib-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="pyvonib-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:trade-federation" /></template>
