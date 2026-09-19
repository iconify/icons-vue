<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuvg6_w_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iuvg6_w_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:stopwatch-sharp" /></template>
