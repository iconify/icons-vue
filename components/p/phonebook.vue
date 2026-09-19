<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzui4_y6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pzui4_y6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phonebook" /></template>
