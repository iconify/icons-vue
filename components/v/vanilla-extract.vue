<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdolnqbey.css';
import '../../css/q/qiz-9kb7a.css';
import '../../css/k/kkhe1jboc.css';
import '../../css/x/x4_9e9-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="fdolnqbey"/><path class="qiz-9kb7a"/><path class="kkhe1jboc"/><path class="x4_9e9-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vanilla-extract" /></template>
