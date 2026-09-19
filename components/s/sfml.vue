<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rldz3bb1z.css';
import '../../css/w/wdrk3cy4t.css';
import '../../css/p/p8wh8o_bf.css';
import '../../css/s/s0qlh1b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rldz3bb1z"/><path class="wdrk3cy4t"/><path class="p8wh8o_bf"/><path class="s0qlh1b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sfml" /></template>
