<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcwdn0bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jcwdn0bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plug-fill-20" /></template>
