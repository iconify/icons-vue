<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhhiamiic.css';
import '../../css/e/efnhhmbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hhhiamiic"/><path class="efnhhmbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tabs-20" /></template>
