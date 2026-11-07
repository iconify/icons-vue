<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dth18jb_c.css';
import '../../css/b/bx1khacep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dth18jb_c"/><path class="bx1khacep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-sun-bold" /></template>
