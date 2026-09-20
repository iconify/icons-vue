<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmjyrqbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjyrqbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mouse-2" /></template>
