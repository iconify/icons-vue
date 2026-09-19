<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1qqbqbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1qqbqbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:skyliner" /></template>
