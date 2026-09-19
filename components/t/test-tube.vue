<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9apszbzh.css';
import '../../css/x/x-t5qxbzm.css';
import '../../css/i/ibuyixdlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f9apszbzh"/><path class="x-t5qxbzm"/><path class="ibuyixdlq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:test-tube" /></template>
