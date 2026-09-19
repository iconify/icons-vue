<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/varwkcb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="varwkcb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:plus-sign-in-square" /></template>
