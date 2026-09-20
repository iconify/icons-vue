<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ivnme8fnn.css';
import '../../css/n/n3zf9obkq.css';
import '../../css/c/c20im5hsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ivnme8fnn"/><path class="n3zf9obkq"/><path class="c20im5hsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:toggle-off-duotone" /></template>
