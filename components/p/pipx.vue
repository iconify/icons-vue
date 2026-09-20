<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbn7w4b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn7w4b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pipx" /></template>
