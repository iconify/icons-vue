<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aedcft.css';
import '../../css/c/chdxye.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aedcft"/><path class="chdxye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-half-twotone" /></template>
