<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekkzrib-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ekkzrib-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:plus-16-solid" /></template>
