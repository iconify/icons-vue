<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwd_u0bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwd_u0bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:typography-off" /></template>
