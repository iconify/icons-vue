<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-2h1_beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h-2h1_beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:x-small-solid" /></template>
