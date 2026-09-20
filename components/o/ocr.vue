<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4ril9bys.css';
import '../../css/j/jpg3fab-z.css';
import '../../css/y/y7lv7g-4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e4ril9bys"/><path class="jpg3fab-z"/><path class="y7lv7g-4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:ocr" /></template>
