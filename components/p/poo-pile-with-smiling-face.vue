<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1pz6obmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1pz6obmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:poo-pile-with-smiling-face" /></template>
