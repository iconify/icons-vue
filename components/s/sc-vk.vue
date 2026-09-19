<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7gvf4b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="t7gvf4b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-vk" /></template>
