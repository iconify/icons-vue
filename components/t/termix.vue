<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzfltwb0i.css';
import '../../css/r/rmhq31bfl.css';
import '../../css/i/iyy4s4bbf.css';
import '../../css/n/n6xqm1b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<rect class="yzfltwb0i"/><rect class="rmhq31bfl"/><path class="iyy4s4bbf"/><path class="n6xqm1b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:termix" /></template>
