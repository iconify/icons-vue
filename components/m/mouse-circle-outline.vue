<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ofi4dze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_ofi4dze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mouse-circle-outline" /></template>
