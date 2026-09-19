<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnlv2sbng.css';
import '../../css/b/b8q2yu59y.css';
import '../../css/b/bp-ry8byp.css';
import '../../css/u/ucfh2zb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnlv2sbng"/><path class="b8q2yu59y"/><ellipse class="bp-ry8byp"/><ellipse class="ucfh2zb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-snapchat-outline" /></template>
