<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-r9ksb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x-r9ksb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:soft-wrap" /></template>
