<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfy3q2bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfy3q2bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-pointer-ban" /></template>
