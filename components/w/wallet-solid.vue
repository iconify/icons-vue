<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-q-dlheo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z-q-dlheo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wallet-solid" /></template>
