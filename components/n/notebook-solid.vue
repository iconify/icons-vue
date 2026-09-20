<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdc7i822q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdc7i822q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:notebook-solid" /></template>
