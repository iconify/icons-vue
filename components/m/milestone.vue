<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpk7xkb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpk7xkb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:milestone" /></template>
