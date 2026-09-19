<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l95p6hgdb.css';
import '../../css/x/xea6o-oef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l95p6hgdb"/><path class="xea6o-oef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:photoshop" /></template>
