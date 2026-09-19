<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_4zw6myr.css';
import '../../css/d/dqmrp9wad.css';
import '../../css/k/ksly09b8o.css';
import '../../css/b/bl5cpf6bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_4zw6myr"/><path class="dqmrp9wad"/><path class="ksly09b8o"/><path class="bl5cpf6bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-reorder" /></template>
