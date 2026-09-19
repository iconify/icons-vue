<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm6fp7b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm6fp7b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pocket" /></template>
