<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0htrpbhr.css';
import '../../css/h/hbcr0mbsz.css';
import '../../css/e/empd4xbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0htrpbhr"/><path class="hbcr0mbsz"/><path class="empd4xbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ray" /></template>
