<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx3y42bar.css';
import '../../css/b/bub6_kbew.css';
import '../../css/f/f9dyx4nnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx3y42bar"/><path class="bub6_kbew"/><path class="f9dyx4nnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:movies-sit-drink-bold" /></template>
