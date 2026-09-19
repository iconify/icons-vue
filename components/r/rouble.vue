<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1eoneb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":767,"height":1024};
const content = `<path class="l1eoneb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rouble" /></template>
