<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeswnpbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":472};
const content = `<path class="jeswnpbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:random" /></template>
