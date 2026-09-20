<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p33odw_cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p33odw_cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-2-outline" /></template>
