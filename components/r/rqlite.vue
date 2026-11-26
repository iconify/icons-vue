<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3r9tub9u.css';
import '../../css/k/k78qywbzi.css';
import '../../css/d/dp-xfwbez.css';
import '../../css/d/dh01pubcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a3r9tub9u"/><path class="k78qywbzi"/><path class="dp-xfwbez"/><path class="dh01pubcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rqlite" /></template>
