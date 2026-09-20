<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl35mubuy.css';
import '../../css/w/wfpw4achp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cl35mubuy"/><path class="wfpw4achp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamystats-light" /></template>
