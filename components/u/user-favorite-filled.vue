<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s27uf9b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s27uf9b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-favorite-filled" /></template>
