<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz7foyb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="cz7foyb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:memorial-10" /></template>
