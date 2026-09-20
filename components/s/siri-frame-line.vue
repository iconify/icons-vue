<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjr9i_a7v.css';
import '../../css/p/pz9kr7bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="jjr9i_a7v"/><path class="pz9kr7bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:siri-frame-line" /></template>
