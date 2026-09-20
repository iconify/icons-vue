<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veysuxbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veysuxbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:recycle-bin-2" /></template>
