<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjxey5bjp.css';
import '../../css/h/hgf0v-b3k.css';
import '../../css/c/cm-f3t2vn.css';
import '../../css/d/dyuvwzb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vjxey5bjp"/><circle class="hgf0v-b3k"/><path class="cm-f3t2vn"/><path class="dyuvwzb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pytorch-wordmark" /></template>
