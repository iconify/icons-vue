<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ivx9b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6ivx9b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:play-solid" /></template>
