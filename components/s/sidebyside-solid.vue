<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kszgptbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kszgptbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:sidebyside-solid" /></template>
