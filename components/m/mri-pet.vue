<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf_l5nbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_l5nbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:mri-pet" /></template>
