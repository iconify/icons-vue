<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ct3xu4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v5ct3xu4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-letter-p" /></template>
