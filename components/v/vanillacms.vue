<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1bf2ch-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="n1bf2ch-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:vanillacms" /></template>
