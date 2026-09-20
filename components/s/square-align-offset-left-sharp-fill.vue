<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6l_u-bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6l_u-bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-left-sharp-fill" /></template>
