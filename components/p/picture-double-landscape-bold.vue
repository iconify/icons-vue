<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx9ddnbmg.css';
import '../../css/j/jq8l55ojp.css';
import '../../css/r/r6q3ycj7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx9ddnbmg"/><path class="jq8l55ojp"/><path class="r6q3ycj7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:picture-double-landscape-bold" /></template>
