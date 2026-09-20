<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6tjmo3jk.css';
import '../../css/r/rbdg38luf.css';
import '../../css/m/mfbnmqh5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="z6tjmo3jk"><path class="rbdg38luf"/><path class="mfbnmqh5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:temperature-fahrenheit" /></template>
