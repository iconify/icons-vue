<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bthpj2-gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="bthpj2-gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:movieclapper" /></template>
