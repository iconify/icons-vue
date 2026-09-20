<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aukfd-bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aukfd-bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:notebook-light" /></template>
