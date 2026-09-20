<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu7bl6bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7bl6bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nvm" /></template>
