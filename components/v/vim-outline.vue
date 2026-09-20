<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3schulug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r3schulug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vim-outline" /></template>
