<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmg3ne9zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hmg3ne9zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:new-file" /></template>
