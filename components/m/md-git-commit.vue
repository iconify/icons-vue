<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuge535qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uuge535qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-git-commit" /></template>
