<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjbwlsbfm.css';
import '../../css/m/mdtq3-bqo.css';
import '../../css/l/l7fvvsb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jjbwlsbfm"/><path class="mdtq3-bqo"/><path class="l7fvvsb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:megaphone-20-bold" /></template>
