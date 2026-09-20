<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coe0unrft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="coe0unrft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:search-filled" /></template>
