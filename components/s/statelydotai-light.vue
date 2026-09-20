<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db7rvqw0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":405};
const content = `<path class="db7rvqw0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:statelydotai-light" /></template>
