<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs3f99brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hs3f99brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:waving-hand-solid" /></template>
