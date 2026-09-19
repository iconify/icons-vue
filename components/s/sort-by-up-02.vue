<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt0f4aciv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0f4aciv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sort-by-up-02" /></template>
