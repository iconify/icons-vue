<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcfac8bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcfac8bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steamdb-light" /></template>
