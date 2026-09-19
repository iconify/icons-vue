<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im7ehtbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="im7ehtbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:o" /></template>
