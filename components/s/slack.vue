<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_nj_bik.css';
import '../../css/y/yfbdwob5o.css';
import '../../css/y/yo40yrbuz.css';
import '../../css/c/ce9c_jbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vh_nj_bik"/><path class="yfbdwob5o"/><path class="yo40yrbuz"/><path class="ce9c_jbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:slack" /></template>
