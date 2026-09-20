<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgr41sxqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kgr41sxqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:remove" /></template>
