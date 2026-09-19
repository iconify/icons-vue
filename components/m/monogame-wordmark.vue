<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkx8at11b.css';
import '../../css/w/wsq0amysy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jkx8at11b"/><path class="wsq0amysy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:monogame-wordmark" /></template>
