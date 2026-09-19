<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-5ogob0g.css';
import '../../css/i/il_nhwj0r.css';
import '../../css/d/dh0pfppzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q-5ogob0g"/><path class="il_nhwj0r"/><path class="dh0pfppzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sanity" /></template>
