<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgld--2ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgld--2ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-circle-solid" /></template>
