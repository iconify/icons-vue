<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufp99g8_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ufp99g8_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:trashfull" /></template>
