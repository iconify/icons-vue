<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7f4xqbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f7f4xqbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:operate-plant" /></template>
