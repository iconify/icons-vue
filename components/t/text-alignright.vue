<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8fymnbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g8fymnbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-alignright" /></template>
