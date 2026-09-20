<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfasz3buw.css';
import '../../css/i/iu6mn3bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xfasz3buw"/><path class="iu6mn3bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:maya" /></template>
