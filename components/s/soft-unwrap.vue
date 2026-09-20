<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3k-pwbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i3k-pwbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:soft-unwrap" /></template>
