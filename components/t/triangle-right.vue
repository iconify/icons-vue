<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b90q36xnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b90q36xnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:triangle-right" /></template>
