<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/banhr5xsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="banhr5xsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pinwheel-solid" /></template>
