<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1np659_m.css';
import '../../css/n/n180x7juo.css';
import '../../css/j/jwnchgn9i.css';
import '../../css/j/j8k9-bcng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x1np659_m"/><path class="n180x7juo"/><path class="jwnchgn9i"/><path class="j8k9-bcng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:portable-solar-20-bold" /></template>
