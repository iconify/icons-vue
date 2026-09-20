<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud64q60rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ud64q60rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:thumb-down" /></template>
