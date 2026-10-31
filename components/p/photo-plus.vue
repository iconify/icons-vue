<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k099k6bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k099k6bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus" /></template>
