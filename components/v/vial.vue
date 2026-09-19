<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_o9ybcwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_o9ybcwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:vial" /></template>
