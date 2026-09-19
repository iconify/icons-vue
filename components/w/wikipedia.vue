<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu-tntvqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fu-tntvqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:wikipedia" /></template>
