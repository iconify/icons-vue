<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5sn9n9c.css';
import '../../css/x/x9950ccly.css';
import '../../css/i/il2mnhbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qh5sn9n9c"/><path class="x9950ccly"/><path class="il2mnhbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:worm-gear-20" /></template>
