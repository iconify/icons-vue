<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl1d0s49v.css';
import '../../css/i/ictwwwp8x.css';
import '../../css/c/c2rntjb-m.css';
import '../../css/k/k0_w5cj4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="bl1d0s49v"/><path class="ictwwwp8x"/><path class="c2rntjb-m"/><circle class="k0_w5cj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ne-4x3" /></template>
