<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgvk4i-fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgvk4i-fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-multiple-group-remix" /></template>
