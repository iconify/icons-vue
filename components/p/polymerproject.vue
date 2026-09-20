<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1sg6xboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1sg6xboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:polymerproject" /></template>
