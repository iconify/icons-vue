<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2eg_5l7t.css';
import '../../css/x/xlm34w3pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z2eg_5l7t"/><path clip-rule="evenodd" class="xlm34w3pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:markdown-mark" /></template>
