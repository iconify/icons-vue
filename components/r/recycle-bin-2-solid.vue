<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nio-28yku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nio-28yku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:recycle-bin-2-solid" /></template>
