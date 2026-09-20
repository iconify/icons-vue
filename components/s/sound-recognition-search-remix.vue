<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5t6nbb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b5t6nbb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sound-recognition-search-remix" /></template>
