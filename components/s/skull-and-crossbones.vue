<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pc0jvxbqt.css';
import '../../css/f/fk5rj3b7q.css';
import '../../css/m/m8b73kr7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pc0jvxbqt"/><path class="fk5rj3b7q"/><path class="m8b73kr7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:skull-and-crossbones" /></template>
