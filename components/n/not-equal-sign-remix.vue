<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1o9flxbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1o9flxbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:not-equal-sign-remix" /></template>
