<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbcopub7q.css';
import '../../css/b/b1n3f83cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="xbcopub7q"/><path class="b1n3f83cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nurse" /></template>
