<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnjdskbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":355,"height":512};
const content = `<path clip-rule="evenodd" class="rnjdskbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nsri-alt" /></template>
