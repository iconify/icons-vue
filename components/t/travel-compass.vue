<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwj6unb5t.css';
import '../../css/k/kcfkgy84u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rwj6unb5t"/><path clip-rule="evenodd" class="kcfkgy84u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-compass" /></template>
