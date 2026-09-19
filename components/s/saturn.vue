<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsn7nt_2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsn7nt_2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:saturn" /></template>
