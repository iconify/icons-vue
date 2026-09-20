<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl22y94ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl22y94ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stretching-2" /></template>
