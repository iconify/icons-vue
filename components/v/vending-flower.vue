<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng_zzxpne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ng_zzxpne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-flower" /></template>
