<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qth6jii9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qth6jii9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:point-up" /></template>
