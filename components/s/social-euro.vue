<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpk8ljbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fpk8ljbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-euro" /></template>
