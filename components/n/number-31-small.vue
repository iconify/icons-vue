<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9fplgbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9fplgbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-31-small" /></template>
