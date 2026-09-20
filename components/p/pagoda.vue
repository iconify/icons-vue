<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcv3k0ieq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lcv3k0ieq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pagoda" /></template>
