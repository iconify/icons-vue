<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjquvbcqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjquvbcqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-down-sharp-fill" /></template>
