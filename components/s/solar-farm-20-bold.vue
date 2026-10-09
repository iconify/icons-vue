<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7b81vbqj.css';
import '../../css/w/w_0bcbclm.css';
import '../../css/b/b-kn6cc_o.css';
import '../../css/e/eiz_f0bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w7b81vbqj"/><path class="w_0bcbclm"/><path class="b-kn6cc_o"/><path class="eiz_f0bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-20-bold" /></template>
