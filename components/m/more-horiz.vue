<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a669i7b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a669i7b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:more-horiz" /></template>
