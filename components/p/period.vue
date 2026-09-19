<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4c5vcbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":77,"height":654};
const content = `<path class="c4c5vcbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:period" /></template>
