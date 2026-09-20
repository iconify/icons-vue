<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcqo_kb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bcqo_kb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sigma" /></template>
