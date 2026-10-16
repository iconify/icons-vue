<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5j847bee.css';
import '../../css/p/pr4dqmbxn.css';
import '../../css/n/n_d0zwbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5j847bee"/><path class="pr4dqmbxn"/><path class="n_d0zwbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-alert-20" /></template>
