<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aayrck8cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aayrck8cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vtx" /></template>
