<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhvkqfn8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhvkqfn8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sound-recognition-search-solid" /></template>
