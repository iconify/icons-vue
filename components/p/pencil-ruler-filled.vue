<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mei0sub7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mei0sub7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-ruler-filled" /></template>
