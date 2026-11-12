<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ria7zub2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ria7zub2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-search" /></template>
