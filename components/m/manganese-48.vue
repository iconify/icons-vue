<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8mtjico.css';
import '../../css/l/l62m84s6k.css';
import '../../css/y/y-2ykkrlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="l62m84s6k"/><path class="y-2ykkrlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:manganese-48" /></template>
