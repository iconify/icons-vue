<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwvj52bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lwvj52bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:question" /></template>
