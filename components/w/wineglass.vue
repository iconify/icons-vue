<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul-fvud4v.css';
import '../../css/j/jvhn8ub7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ul-fvud4v"/><path class="jvhn8ub7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:wineglass" /></template>
