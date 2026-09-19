<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha1ngc8fk.css';
import '../../css/v/vrz9w3bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ha1ngc8fk"/><path class="vrz9w3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:split" /></template>
