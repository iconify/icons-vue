<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk0_bffgj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b8ykfyb9e.css';
import '../../css/w/w9yqwqbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk0_bffgj secondary"/><g class="dt0cm9dhy primary"><path class="b8ykfyb9e"/><path class="w9yqwqbyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tag-duo" /></template>
