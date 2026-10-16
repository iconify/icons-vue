<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdaustbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1575.6,"height":1575.6,"left":82.5,"top":-157.5};
const content = `<path class="tdaustbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mailhog" /></template>
