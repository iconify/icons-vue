<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_ui4beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fk_ui4beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:remote" /></template>
