<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4oyxi0fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4oyxi0fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:play-off-filled" /></template>
