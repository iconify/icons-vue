<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2gyfudfs.css';
import '../../css/b/b5kui9phr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p2gyfudfs"/><path class="b5kui9phr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:ongoing-conversation-ltr" /></template>
