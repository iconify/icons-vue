<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkq8gguhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vkq8gguhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone" /></template>
