<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxd6jfy2h.css';
import '../../css/c/chzkkvbwn.css';
import '../../css/k/k2xeydb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zxd6jfy2h"/><path class="chzkkvbwn"/><path class="k2xeydb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toolbox-20" /></template>
