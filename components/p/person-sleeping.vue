<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8w3bmb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z8w3bmb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping" /></template>
