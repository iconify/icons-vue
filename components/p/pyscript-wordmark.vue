<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygjwjl6cp.css';
import '../../css/j/j15unt4yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ygjwjl6cp"/><path class="j15unt4yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pyscript-wordmark" /></template>
