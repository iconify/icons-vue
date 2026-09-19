<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-aenvbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="g-aenvbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mypictures" /></template>
