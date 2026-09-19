<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luaii9byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="luaii9byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pssquare" /></template>
