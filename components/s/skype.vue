<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp71t6fky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="fp71t6fky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:skype" /></template>
