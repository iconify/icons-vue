<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg8xfks_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gg8xfks_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:plus" /></template>
