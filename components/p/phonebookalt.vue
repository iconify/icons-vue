<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg8u_7bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fg8u_7bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phonebookalt" /></template>
