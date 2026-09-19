<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh_576bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jh_576bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moonnew" /></template>
