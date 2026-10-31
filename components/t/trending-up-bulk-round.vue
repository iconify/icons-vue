<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw6890bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw6890bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-up-bulk-round" /></template>
