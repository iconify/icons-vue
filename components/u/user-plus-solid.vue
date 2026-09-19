<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-c6jlbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-c6jlbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-plus-solid" /></template>
