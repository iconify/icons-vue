<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn6i_fowy.css';
import '../../css/a/adhtr2bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn6i_fowy"/><path class="adhtr2bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refund-cny-fill" /></template>
