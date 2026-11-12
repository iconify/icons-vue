<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7bxye5gu.css';
import '../../css/f/f0tftrz9n.css';
import '../../css/m/m41x7yb6k.css';
import '../../css/o/o1r8z0b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7bxye5gu"/><path class="f0tftrz9n"/><path class="m41x7yb6k"/><path class="o1r8z0b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickbars" /></template>
