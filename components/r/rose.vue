<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ora3me5pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ora3me5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:rose" /></template>
