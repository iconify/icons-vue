<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hf35dlb5y.css';
import '../../css/s/s_l845bvk.css';
import '../../css/b/b98f61baq.css';
import '../../css/t/t_fn09dzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="hf35dlb5y"/><path class="s_l845bvk"/><circle class="b98f61baq"/><circle class="t_fn09dzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:mobile" /></template>
