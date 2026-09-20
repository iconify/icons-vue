<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad0xoryqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ad0xoryqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stop-solid" /></template>
