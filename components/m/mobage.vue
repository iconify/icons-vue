<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7rw1rb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":740};
const content = `<path class="j7rw1rb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:mobage" /></template>
