<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk3daea8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yk3daea8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wifi-16-solid" /></template>
