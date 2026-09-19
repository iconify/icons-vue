<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzijbqbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vzijbqbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:topbuzz" /></template>
