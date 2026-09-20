<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2cvywb3g.css';
import '../../css/x/x1i6yhgya.css';
import '../../css/k/k5gujvbth.css';
import '../../css/c/c1r-wtblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2cvywb3g"/><path clip-rule="evenodd" class="x1i6yhgya"/><path clip-rule="evenodd" class="k5gujvbth"/><path clip-rule="evenodd" class="c1r-wtblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pex" /></template>
