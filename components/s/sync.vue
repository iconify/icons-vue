<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8x-rqbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8x-rqbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sync" /></template>
