<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb8mpqbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fb8mpqbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:map" /></template>
