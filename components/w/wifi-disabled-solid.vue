<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7sl9q-7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f7sl9q-7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-disabled-solid" /></template>
