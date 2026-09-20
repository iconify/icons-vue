<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hftpl1bgl.css';
import '../../css/l/lq8j-ubmb.css';
import '../../css/a/ay3n_xfrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hftpl1bgl"/><path class="lq8j-ubmb"/><path class="ay3n_xfrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:robot" /></template>
