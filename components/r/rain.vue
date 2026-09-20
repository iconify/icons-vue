<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dohg0wbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dohg0wbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:rain" /></template>
