<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfwgsqbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfwgsqbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandglass-2-fill" /></template>
