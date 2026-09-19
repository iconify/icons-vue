<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynhhlqb6o.css';
import '../../css/k/kkl6jsbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="kkl6jsbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:sound-recording-copyright" /></template>
