<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jki1m8b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jki1m8b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:paperplane" /></template>
