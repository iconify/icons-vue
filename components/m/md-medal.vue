<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytsqaqbxb.css';
import '../../css/y/y4cyulhsa.css';
import '../../css/s/snt_cnzej.css';
import '../../css/v/vu2rk5hjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytsqaqbxb"/><circle class="y4cyulhsa"/><path class="snt_cnzej"/><path class="vu2rk5hjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-medal" /></template>
