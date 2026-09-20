<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhdm0f4my.css';
import '../../css/n/nzkrizz9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhdm0f4my"/><path clip-rule="evenodd" class="nzkrizz9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mav" /></template>
