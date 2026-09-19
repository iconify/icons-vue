<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwb4vcbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwb4vcbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mug-hot-outline" /></template>
