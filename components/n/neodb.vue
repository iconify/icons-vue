<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xik-vs_jl.css';
import '../../css/o/owdhvpbwp.css';
import '../../css/k/kt2xtwbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xik-vs_jl"/><path class="owdhvpbwp"/><path class="kt2xtwbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neodb" /></template>
