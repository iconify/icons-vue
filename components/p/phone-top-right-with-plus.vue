<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4es6rmzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a4es6rmzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-with-plus" /></template>
