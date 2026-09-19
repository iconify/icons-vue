<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykos20fnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykos20fnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:not-element-of" /></template>
