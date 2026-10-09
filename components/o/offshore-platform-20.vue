<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp1-1hbdm.css';
import '../../css/v/v0b2vloiw.css';
import '../../css/a/a8mu2cb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zp1-1hbdm"/><path class="v0b2vloiw"/><path class="a8mu2cb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-platform-20" /></template>
