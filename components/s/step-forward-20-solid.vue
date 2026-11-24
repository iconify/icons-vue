<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eee9e2wkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eee9e2wkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:step-forward-20-solid" /></template>
