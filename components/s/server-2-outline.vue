<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0knn25cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0knn25cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-2-outline" /></template>
