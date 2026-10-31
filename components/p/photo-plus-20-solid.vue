<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7k8nrb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g7k8nrb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus-20-solid" /></template>
