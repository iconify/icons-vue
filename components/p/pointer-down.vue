<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhgj0q6xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgj0q6xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-down" /></template>
