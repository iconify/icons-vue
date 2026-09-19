<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa2c9cb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa2c9cb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:server-solid" /></template>
