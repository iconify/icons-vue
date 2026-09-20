<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqb0h2zhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kqb0h2zhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-on-inclined-swing" /></template>
