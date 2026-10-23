<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqbma1f2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqbma1f2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:rectangle-vertical" /></template>
