<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb6fyhe2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cb6fyhe2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stickynotealt" /></template>
