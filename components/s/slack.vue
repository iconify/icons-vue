<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmhysybif.css';
import '../../css/s/sbtxsib7i.css';
import '../../css/e/erzbhu1-s.css';
import '../../css/b/bqg7jocgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhysybif"/><path class="sbtxsib7i"/><path class="erzbhu1-s"/><path class="bqg7jocgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:slack" /></template>
