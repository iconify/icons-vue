<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr4i-mvju.css';
import '../../css/p/pqy87ebie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr4i-mvju"/><path class="pqy87ebie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:raisedhandsfingerssplayed" /></template>
