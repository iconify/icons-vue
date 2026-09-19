<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_by2_hg.css';
import '../../css/s/stthulblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_by2_hg"/><path class="stthulblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:search-alt" /></template>
