<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/s/ssaqwk.css';
import '../../css/b/b6e05i.css';
import '../../css/b/blqfnz.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ssaqwk"/><path class="a0m25c b6e05i"/><path class="a0m25c blqfnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:menu" /></template>
