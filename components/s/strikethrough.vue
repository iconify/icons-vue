<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brox0--5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="brox0--5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:strikethrough" /></template>
