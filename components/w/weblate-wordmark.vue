<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm0hikb7f.css';
import '../../css/f/fc2_4nl4g.css';
import '../../css/v/vczsbmbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zm0hikb7f"/><path clip-rule="evenodd" class="fc2_4nl4g"/><path class="vczsbmbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:weblate-wordmark" /></template>
