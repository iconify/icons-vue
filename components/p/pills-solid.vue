<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-v06lbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-v06lbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pills-solid" /></template>
