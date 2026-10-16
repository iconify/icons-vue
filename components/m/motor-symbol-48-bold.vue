<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_iwi87h.css';
import '../../css/v/vc8qn24vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tf_iwi87h"/><path class="vc8qn24vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motor-symbol-48-bold" /></template>
