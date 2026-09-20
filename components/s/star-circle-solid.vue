<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npy_5y7xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="npy_5y7xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-circle-solid" /></template>
