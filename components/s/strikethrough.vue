<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnuccabyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnuccabyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:strikethrough" /></template>
