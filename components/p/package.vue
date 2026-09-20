<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqhkikbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pqhkikbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:package" /></template>
