<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj3wil8tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wj3wil8tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:microphone" /></template>
