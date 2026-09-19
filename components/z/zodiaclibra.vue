<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5c6ykbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r5c6ykbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zodiaclibra" /></template>
