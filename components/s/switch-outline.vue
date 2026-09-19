<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjxr91cpr.css';
import '../../css/j/jq4bsyb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pjxr91cpr"/><rect class="jq4bsyb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:switch-outline" /></template>
