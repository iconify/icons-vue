<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm9liwb3f.css';
import '../../css/g/g451w2_7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm9liwb3f"/><path class="g451w2_7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:space-rocket-earth-bold" /></template>
