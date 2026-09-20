<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4y5y6blb.css';
import '../../css/n/nor-6jbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="v4y5y6blb"/><path class="nor-6jbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:star-fat-half-2" /></template>
