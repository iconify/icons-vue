<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6wedk6gg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b4a62x58a.css';
import '../../css/h/h1zbsh5sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z6wedk6gg"/><g class="dt0cm9dhy primary"><path class="b4a62x58a"/><path class="h1zbsh5sl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sun-dim-duo" /></template>
