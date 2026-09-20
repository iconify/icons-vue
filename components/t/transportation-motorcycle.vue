<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4uiwqbnk.css';
import '../../css/i/it_a7iblf.css';
import '../../css/z/z1wf33p3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b4uiwqbnk"/><path class="it_a7iblf"/><path class="z1wf33p3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:transportation-motorcycle" /></template>
