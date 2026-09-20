<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_jyd0s0l.css';
import '../../css/s/sk9-dtbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_jyd0s0l"/><path clip-rule="evenodd" class="sk9-dtbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:success-32" /></template>
