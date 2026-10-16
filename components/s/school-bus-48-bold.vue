<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwgm7fbxw.css';
import '../../css/c/cdyatobkg.css';
import '../../css/z/zcwxudbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bwgm7fbxw"/><path class="cdyatobkg"/><path class="zcwxudbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:school-bus-48-bold" /></template>
