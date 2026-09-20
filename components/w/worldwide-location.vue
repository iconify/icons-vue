<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_lrjbcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="j_lrjbcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:worldwide-location" /></template>
