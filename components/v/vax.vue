<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmmc_bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcmmc_bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vax" /></template>
