<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8brmzbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b8brmzbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:star-one" /></template>
