<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pekdaxbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pekdaxbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-round" /></template>
