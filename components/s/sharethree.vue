<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2hpmjtqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="c2hpmjtqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sharethree" /></template>
