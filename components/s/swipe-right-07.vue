<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se3kvac6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se3kvac6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-right-07" /></template>
