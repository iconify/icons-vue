<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh1u6cmlr.css';
import '../../css/f/flmjdj3we.css';
import '../../css/x/xu50pybzl.css';
import '../../css/o/o2rektbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jh1u6cmlr"/><path class="flmjdj3we"/><path class="xu50pybzl"/><path class="o2rektbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-strands" /></template>
