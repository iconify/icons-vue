<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj3o6hooc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj3o6hooc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:table-rows-line" /></template>
