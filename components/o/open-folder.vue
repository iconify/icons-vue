<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgl6b1yyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bgl6b1yyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:open-folder" /></template>
