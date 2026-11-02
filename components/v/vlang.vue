<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko5dwac9v.css';
import '../../css/q/q_5fvp18n.css';
import '../../css/q/qua1n-5tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ko5dwac9v"/><path class="q_5fvp18n"/><path class="qua1n-5tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vlang" /></template>
