<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-l6l33py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="i-l6l33py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:microphonethree" /></template>
