<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njdpvjbzg.css';
import '../../css/f/fmukgjbig.css';
import '../../css/j/jlr84fbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="njdpvjbzg"/><path class="fmukgjbig"/><path class="jlr84fbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pig-20" /></template>
