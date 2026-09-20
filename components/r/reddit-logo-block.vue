<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abe0kqbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abe0kqbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:reddit-logo-block" /></template>
