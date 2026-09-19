<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id7naxmdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="id7naxmdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:prolog" /></template>
