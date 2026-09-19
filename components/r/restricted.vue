<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsy0p32fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lsy0p32fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:restricted" /></template>
