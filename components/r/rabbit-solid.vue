<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi8-qhbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi8-qhbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rabbit-solid" /></template>
