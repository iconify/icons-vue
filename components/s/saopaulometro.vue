<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7fzjmd8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7fzjmd8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:saopaulometro" /></template>
