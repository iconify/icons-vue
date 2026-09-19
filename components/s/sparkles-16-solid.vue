<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsu03k0ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bsu03k0ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sparkles-16-solid" /></template>
