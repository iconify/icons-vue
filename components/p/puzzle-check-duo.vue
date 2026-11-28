<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m60pqtldl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h0a8jr8wu.css';
import '../../css/q/q96y81bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m60pqtldl secondary"/><g class="dt0cm9dhy primary"><path class="h0a8jr8wu"/><path class="q96y81bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-check-duo" /></template>
