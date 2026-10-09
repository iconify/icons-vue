<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsc21xyjd.css';
import '../../css/j/j9dld7jrj.css';
import '../../css/i/ipo79vlap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fsc21xyjd"/><path class="j9dld7jrj"/><path class="ipo79vlap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safe-20" /></template>
