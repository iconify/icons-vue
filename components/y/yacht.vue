<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcwmn2dil.css';
import '../../css/r/rrczhp0ig.css';
import '../../css/b/b3q-odbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hcwmn2dil"/><path class="rrczhp0ig"/><path class="b3q-odbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yacht" /></template>
