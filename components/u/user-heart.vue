<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow47gmbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow47gmbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-heart" /></template>
