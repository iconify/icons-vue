<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4butrblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s4butrblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-list-fill-20" /></template>
