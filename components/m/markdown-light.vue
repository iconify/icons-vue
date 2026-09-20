<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a89cky7-t.css';
import '../../css/a/ajlhn96ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":208,"height":128};
const content = `<path clip-rule="evenodd" class="a89cky7-t"/><path class="ajlhn96ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:markdown-light" /></template>
