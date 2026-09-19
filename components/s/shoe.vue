<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1tooob1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":472};
const content = `<path class="w1tooob1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:shoe" /></template>
