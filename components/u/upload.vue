<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cku-a-_in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cku-a-_in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:upload" /></template>
