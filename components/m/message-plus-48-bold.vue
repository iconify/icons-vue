<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy-u42bhp.css';
import '../../css/j/jcjy32bzm.css';
import '../../css/a/al63s1bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zy-u42bhp"/><path class="jcjy32bzm"/><path class="al63s1bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-plus-48-bold" /></template>
