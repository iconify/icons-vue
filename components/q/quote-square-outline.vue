<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/b0lqkvb9p.css';
import '../../css/g/g8ko324ru.css';
import '../../css/e/eszrb1bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="b0lqkvb9p"/><path class="g8ko324ru"/><path class="eszrb1bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quote-square-outline" /></template>
