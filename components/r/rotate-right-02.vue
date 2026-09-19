<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2-h72ynu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-h72ynu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-right-02" /></template>
