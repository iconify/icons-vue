<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enc17mb1s.css';
import '../../css/l/l7hcm5_mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="enc17mb1s"/><path class="l7hcm5_mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:next" /></template>
