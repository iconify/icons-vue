<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9xz5fzpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9xz5fzpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mic-detailed-line" /></template>
