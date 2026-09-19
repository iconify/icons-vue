<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvm3z5b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvm3z5b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tree-02" /></template>
