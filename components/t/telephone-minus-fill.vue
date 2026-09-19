<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5_hmb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="od5_hmb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-minus-fill" /></template>
