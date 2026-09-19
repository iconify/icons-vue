<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmf2jnxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="ftmf2jnxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pslone" /></template>
