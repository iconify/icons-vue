<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2g6lqbdb.css';
import '../../css/f/fnwhem6it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2g6lqbdb"/><path class="fnwhem6it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-minimalistic-bold-duotone" /></template>
