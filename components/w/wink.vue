<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8tdxbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":698};
const content = `<path class="jg8tdxbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:wink" /></template>
