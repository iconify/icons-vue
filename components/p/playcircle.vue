<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg0k5bz1x.css';
import '../../css/d/d47xi2b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mg0k5bz1x"/><path class="d47xi2b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:playcircle" /></template>
