<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjvpa0utv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjvpa0utv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wolverine-claws" /></template>
