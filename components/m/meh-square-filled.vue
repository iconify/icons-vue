<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whdn7t8on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whdn7t8on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:meh-square-filled" /></template>
