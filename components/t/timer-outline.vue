<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6yzo2b5e.css';
import '../../css/q/qzignebpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6yzo2b5e"/><path class="qzignebpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:timer-outline" /></template>
