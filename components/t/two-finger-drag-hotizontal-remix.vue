<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp2kr3bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fp2kr3bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:two-finger-drag-hotizontal-remix" /></template>
