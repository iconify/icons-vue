<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knr_o8bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knr_o8bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:unilever" /></template>
