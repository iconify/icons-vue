<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgkj53bit.css';
import '../../css/o/o11kupslz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgkj53bit"/><path class="o11kupslz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-circle-bold-duotone" /></template>
