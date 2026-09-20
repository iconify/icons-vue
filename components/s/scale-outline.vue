<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn-0ytboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn-0ytboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scale-outline" /></template>
