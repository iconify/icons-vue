<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2j54kbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c2j54kbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sort-z-to-a-filled" /></template>
