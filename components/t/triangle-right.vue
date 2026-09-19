<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s19bvnbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s19bvnbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-right" /></template>
