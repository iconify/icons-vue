<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fatbecbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fatbecbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-slash-20-solid" /></template>
