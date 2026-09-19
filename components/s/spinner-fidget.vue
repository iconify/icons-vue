<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rynbiubyg.css';
import '../../css/d/dojgfibbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="rynbiubyg"/><path class="dojgfibbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:spinner-fidget" /></template>
