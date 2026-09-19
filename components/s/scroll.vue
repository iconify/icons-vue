<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yccp5dbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yccp5dbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scroll" /></template>
