<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_nqm2quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e_nqm2quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:unavailable-16" /></template>
