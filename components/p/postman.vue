<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6n-h328k.css';
import '../../css/r/rjwj9migx.css';
import '../../css/d/domzjoixq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i6n-h328k"/><path class="rjwj9migx"/><path class="domzjoixq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:postman" /></template>
