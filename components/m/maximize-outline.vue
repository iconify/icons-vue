<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm30exbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm30exbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:maximize-outline" /></template>
