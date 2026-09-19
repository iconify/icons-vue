<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwnkqbkpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwnkqbkpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:sword" /></template>
