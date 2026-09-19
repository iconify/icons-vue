<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c-xjt6unr.css';
import '../../css/s/sgj193bua.css';
import '../../css/e/emzmn0o4c.css';
import '../../css/f/fpzasvuqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c-xjt6unr"/><path class="sgj193bua"/><path class="emzmn0o4c"/><path class="fpzasvuqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:turn-sign-outline" /></template>
