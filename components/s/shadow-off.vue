<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz69n3bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz69n3bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shadow-off" /></template>
