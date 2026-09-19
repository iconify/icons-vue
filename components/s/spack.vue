<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h27h8qbda.css';
import '../../css/g/giuvwzbiq.css';
import '../../css/c/ckfq98akt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h27h8qbda"/><path class="giuvwzbiq"/><path class="ckfq98akt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spack" /></template>
