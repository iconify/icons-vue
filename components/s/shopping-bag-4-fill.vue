<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msney2gri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msney2gri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-4-fill" /></template>
