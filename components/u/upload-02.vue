<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqc2czb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqc2czb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:upload-02" /></template>
