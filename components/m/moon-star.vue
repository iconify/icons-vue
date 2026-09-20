<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks_24obqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks_24obqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:moon-star" /></template>
