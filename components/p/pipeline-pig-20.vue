<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twj580cwe.css';
import '../../css/z/zfu5nqcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="twj580cwe"/><path class="zfu5nqcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-pig-20" /></template>
