<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsq9f2bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tsq9f2bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:play-circle-solid" /></template>
