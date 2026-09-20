<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwy_4lplo.css';
import '../../css/n/n2zz0dpiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dwy_4lplo"/><ellipse class="n2zz0dpiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:tag" /></template>
