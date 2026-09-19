<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp50m7tvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tp50m7tvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-check-16-solid" /></template>
