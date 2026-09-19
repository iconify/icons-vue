<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-tzf4blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d-tzf4blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-yen-circle-fill" /></template>
