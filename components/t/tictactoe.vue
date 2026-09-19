<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez88bsbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ez88bsbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tictactoe" /></template>
