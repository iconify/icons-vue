<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x579hjb9j.css';
import '../../css/a/ad8vvnbjm.css';
import '../../css/j/j1dztmbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x579hjb9j"/><path class="ad8vvnbjm"/><path class="j1dztmbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:postman-wordmark" /></template>
