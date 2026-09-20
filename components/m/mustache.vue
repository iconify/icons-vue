<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sno_jmu9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sno_jmu9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:mustache" /></template>
