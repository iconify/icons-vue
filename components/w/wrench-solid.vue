<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcg52k0qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcg52k0qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wrench-solid" /></template>
