<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/e6c-cgbkv.css';
import '../../css/p/pcjn26jew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e6c-cgbkv"/><path class="pcjn26jew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-apple" /></template>
